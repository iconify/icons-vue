<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bo3135spk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:note-alt-outline-sharp" /></template>
<style>
.bo3135spk {
  fill: currentColor;
  d: path("M7.77 16.23h1.022l5.924-5.872l-1.074-1.074l-5.873 5.874zm7.492-6.418L16.43 8.63l-1.062-1.062l-1.18 1.17zM4 20V4h6.316q-.137-.766.366-1.383Q11.184 2 12 2q.835 0 1.338.617T13.685 4H20v16zm1-1h14V5H5zm7.538-14.77q.212-.213.212-.538t-.212-.537T12 2.942t-.537.213t-.213.537t.213.538t.537.212t.538-.212M5 19V5z");
}

</style>
