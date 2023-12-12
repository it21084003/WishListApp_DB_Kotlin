# WishListApp_DB_Kotlin





plugins {
    id("kotlin-kapt")
    }
    
dependencies {

    val nav_version = "2.7.5"
    val compose_version = "1.6.0-beta02"
    val room = "2.6.1"

    //Room
    implementation("androidx.room:room-common:$room")
    implementation("androidx.room:room-ktx:$room")
    kapt("androidx.room:room-compiler:$room")

    implementation("androidx.navigation:navigation-compose:$nav_version")
    implementation("androidx.core:core-ktx:1.12.0")
    implementation("androidx.compose.ui:ui:$compose_version")
    implementation("androidx.compose.material:material:$compose_version")
    implementation("androidx.compose.ui:ui-tooling-preview:$compose_version")

    }


<application
        android:name=".WishListApp" >

</application>
