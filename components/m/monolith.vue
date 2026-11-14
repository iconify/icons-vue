<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d65ijqbgv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:monolith" /></template>
<style>
.d65ijqbgv {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m7.97 1.97l-3.5 3.5q-.052.051-.092.111q-.041.061-.069.128t-.043.138t-.016.144t.012.144t.04.14q.027.067.066.129q.039.061.089.114q-.207.512-.207 1.232v12q0 1.036.732 1.768t1.768.732h7q.641 0 1.165-.28q.026.031.055.06q.105.106.243.163t.287.057t.287-.057t.243-.163l3.5-3.5q.106-.105.163-.243T19.75 18V2.5q0-.147-.055-.283t-.158-.24l-.007-.007q-.105-.106-.243-.163T19 1.75H8.5q-.149 0-.287.057t-.243.163m.841 1.28h8.378L14.97 5.47q-.029.029-.055.06q-.524-.28-1.165-.28H6.811zm7.219 3.28l2.22-2.219v13.378l-2 2V7.75q0-.641-.28-1.165q.031-.026.06-.055");
}

</style>
