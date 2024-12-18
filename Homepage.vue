<template>
  <v-card class="mx-auto" color="grey-lighten-3" max-width="448">
    <v-layout>
      <v-app-bar
        color="teal-darken-4"
        image="https://picsum.photos/1920/1080?random"
      >
        <template v-slot:image>
          <v-img
            gradient="to top right, rgba(19,84,122,.8), rgba(128,208,199,.8)"
          ></v-img>
        </template>

        <template v-slot:prepend>
          <v-app-bar-nav-icon></v-app-bar-nav-icon>
        </template>

        <v-app-bar-title>SimpleNotes CSIT</v-app-bar-title>

        <v-spacer></v-spacer>

        <v-btn icon>
          <v-icon>mdi-magnify</v-icon>
        </v-btn>

        <v-btn icon>
          <v-icon>mdi-heart</v-icon>
        </v-btn>

        <v-btn icon>
          <v-icon>mdi-dots-vertical</v-icon>
        </v-btn>
      </v-app-bar>

      <v-main>
        <v-container fluid>
          <v-row 
            width="1000px">
            <v-col
              v-for="n in 1"
              :key="n"
              cols="20"
              width="200px"
            >
              <v-card
                 color="red"
                 width="5000px"
               >
                 <v-card-text>
                 <h1>First Semester</h1><br>
                  <br>

                  => 5 subjects
                  </v-card-text>
                
                
              </v-card>
               <v-card
                 color="blue"
                 width="5000px"
               >
                 <v-card-text>
                 <h1>Second Semester</h1><br>
                  <br>

                  => 5 subjects
                  </v-card-text>
                
                
              </v-card>
               <v-card
                 color="yellow"
                 width="5000px"
               >
                 <v-card-text>
                 <h1>Third Semester</h1><br>
                  <br>

                  => 5 subjects
                  </v-card-text>
                
                
              </v-card>
               <v-card
                 color="green"
                 width="5000px"
               >
                 <v-card-text>
                 <h1>Fourth Semester</h1><br>
                  <br>

                  => 5 subjects
                  </v-card-text>
                
                
              </v-card>
            </v-col>
          </v-row>
        </v-container>
      </v-main>
    </v-layout>
  </v-card>
</template>
<script setup>

</script>

<style scoped>
 


</style>