# hydrolibrary
using system;
namespace UtilityLibrary
{
Public Static Class StringLibrary 
{
Public Static bool StartWithUpper(this string str)
{

If (String.IsNullorWhiteSpace(srr))
    return false;
   Char ch = str[0];
   return Char.IsUpper (ch);
   }
   }
   }

The class library, UtilityLibraries.StringLibrary, contains a method named StartsWithUpper, which returns a Boolean value that indicates whether the current string instance begins with an uppercase character. The Unicode standard distinguishes uppercase characters from lowercase characters. The Char.IsUpper(Char) method returns true if a character is uppercase.
