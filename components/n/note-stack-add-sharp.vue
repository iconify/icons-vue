<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j_scgh01f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:note-stack-add-sharp" /></template>
<style>
.j_scgh01f {
  fill: currentColor;
  d: path("M8 21V7.994h13v8.583L16.577 21zm-2.988-3.194L2.752 5.01l12.794-2.259l.504 2.864H5.617v12.082zM14 18h1v-3h3v-1h-3v-3h-1v3h-3v1h3z");
}

</style>
