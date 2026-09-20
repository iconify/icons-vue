<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rf1udsbxb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:stop-screen-share-outline-sharp" /></template>
<style>
.rf1udsbxb {
  fill: currentColor;
  d: path("M14.425 11.575L11.85 9H13V7l3 3zM20.7 17.85L18.85 16H20V5H7.85l-2-2H22v14.85zm-.2 5.45L18.2 21H1v-2h15.175l-1-1H2V4.85L.7 3.5l1.4-1.4l19.8 19.8zM10 12.85V14H8v-2q0-.275.025-.525t.15-.475L4 6.825V16h9.15zM8.575 11.4");
}

</style>
