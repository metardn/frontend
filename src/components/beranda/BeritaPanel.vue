<template>
  <div>
    <v-card flat>
      <p></p>
      <v-row>
        <v-col>
          <h2>BERITA</h2>
        </v-col>
        <v-col>
          <a
            href="#"
            class="text-decoration-underline"
          >Lihat semua</a>
        </v-col>
        <v-col cols="9"></v-col>
      </v-row>
      <v-row>
        <v-col class=""><BeritaCard></BeritaCard></v-col>
        <v-col class=""><BeritaCard></BeritaCard></v-col>
        <v-col class=""><BeritaCard></BeritaCard></v-col>
        <v-col class=""><BeritaCard></BeritaCard></v-col>
        <v-col class=""><BeritaCard></BeritaCard></v-col>
      </v-row>
    </v-card>
  </div>
</template>

<script>
import BeritaCard from './BeritaCard.vue'

export default {
  name: 'App',
  components: {
    BeritaCard
  }
}
</script>