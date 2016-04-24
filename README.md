# BinaryTree-
#include<iostream>

using namespace std;
template<class T>

struct BinaryTreeNode
{
  T _data;
  BinaryTreeNode<T>* _left;//left child
  BinaryTreeNode<T>* _right;//right child
  
  BinaryTreeNode(const T &x)//creat Node
      :_data(x)
      ,_left(NULL)
      ,_right(NULL)
  {}
};

