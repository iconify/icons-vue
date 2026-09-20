<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ekb1ubt6f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:nest-cam-wall-mount-outline-sharp" /></template>
<style>
.ekb1ubt6f {
  fill: currentColor;
  d: path("M3.953 15.822q-.472-.475-.472-1.142V8.215q0-.667.475-1.139q.476-.472 1.144-.472t1.14.475t.472 1.146q.702-1.26 1.966-2.017Q9.942 5.45 11.5 5.45q1.103 0 2.11.42t1.779 1.192l5.013 5.013l-7.752 7.79l-5.039-5.026q-.275-.276-.497-.56t-.403-.604v1.006q0 .666-.475 1.14q-.476.475-1.143.475t-1.14-.474M7 10.925q0 .9.338 1.725t.987 1.475l4.325 4.325L19 12.075L14.675 7.75q-.65-.65-1.462-.988T11.5 6.426q-1.875 0-3.187 1.313T7 10.925m6 1.52");
}

</style>
