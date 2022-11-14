# Adapter design pattern

Repository with source code of the examples used in the classes about the design pattern Adapter, taught by Rodrigo Martins Pagliares at UNIFAL-MG.

## Examples


### 01 - Weapon Game

In this example, I demonstrate the use of the Adapter Design Pattern in order to use a third-party class in our weapon game. We don't have the source code of the third-party classs (but we have the Java doc). In addition to that, we don't want to change our Weapon interface to not break all of our classes that implement that interface. The third party class represents a ShotGun to be used by our game Character.


### 02 - CD table

This example demonstrates how developers use the Adapter design pattern in order to adapt a domain specific interface (list of cds) to become compatible with the AbstractTableModel required by the Swing JTable component. By using the design pattern Adapter, the example shows the list of CDs in the JTable.


### 03 - Stub

This example demonstrates the concept of Stub (empty interface implementation to ease the task of overriding interfaces methods that are not needed by a developer). The example illustrates the use of the MouseAdapter stub class, part of the Java SE Swing library. 

As we can see form the name, MouseAdapter is an implementation of the design pattern adapter in the sense that it adapts the interface of an interface to  MouseAdapter interface that can be inherited by a domain specific class, overriding only the methods needed.

Although Java SE developers named the class MouseAdapter, some people prefer to see it as a implementation of the Facade design pattern.
