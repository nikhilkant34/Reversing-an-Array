# Reversing-an-Array
/*An n element array stories the values of n number of integers and then the array is reversed and the reversed array is returned. */
int main()
{
    int size;
    cin>> size;
    int arr[size]; 
    for (int i=0;i<size; i++)
    {
        cin>>arr[i];
    }
    for (int i=size-1;i>=0; i--)
    {
        cout<<arr[i]<<" ";
    }
    return 0;
}    
