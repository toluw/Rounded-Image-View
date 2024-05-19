# Rounded-Image-View
Rounded ImageView to be usefull for profiles pictures and other similar usage. It inherits from ImageView and thus you can use all the methods associated of a typical imageview

# Steps for integration

1. Add it in your root build.gradle at the end of repositories:
```gradle
dependencyResolutionManagement {
		repositoriesMode.set(RepositoriesMode.FAIL_ON_PROJECT_REPOS)
		repositories {
			mavenCentral()
			maven { url 'https://jitpack.io' }
		}
	}
 ```

 2. Add the dependency to your app level build.gradle
```gradle
     dependencies {
	        implementation 'com.github.toluw:Rounded-Image-View:1.6'
	}
 ```

 # Usage
 
 Add the RoundeImageView to your xml layout
 ```xml
 <com.toluw.circularimageview.RoundedImageView
    app:layout_constraintTop_toTopOf="parent"
    app:layout_constraintBottom_toBottomOf="parent"
    app:layout_constraintStart_toStartOf="parent"
    app:layout_constraintEnd_toEndOf="parent"
    android:src="@drawable/ic_play"
    android:layout_width="wrap_content"
    android:layout_height="wrap_content"/>
     ```
