<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n6586-bdj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:pinboard-unread-outline-sharp" /></template>
<style>
.n6586-bdj {
  fill: currentColor;
  d: path("m6.808 21l-.5-.5v-4.27H3v-1l1.423-2.86V9.384H3v-1h7.616v1H9.192v2.984l1.424 2.862v1H7.308v4.27zm-2.662-5.77H9.47l-1.278-2.54V9.385H5.423v3.304zm11.585-7.959Q15 6.544 15 5.502t.729-1.771T17.498 3t1.771.729T20 5.498t-.728 1.771t-1.77.731t-1.771-.728M13.042 6H3V5h10.042q-.011.116-.026.238q-.016.12-.016.252t.016.253t.026.257m-.6 13v-1H20V9.21q.292-.18.545-.39T21 8.346V19z");
}

</style>
