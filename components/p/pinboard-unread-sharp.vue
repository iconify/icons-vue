<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cjqj4gfcd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:pinboard-unread-sharp" /></template>
<style>
.cjqj4gfcd {
  fill: currentColor;
  d: path("m6.808 21l-.5-.5v-4.27H3v-1l1.423-2.86V9.384H3v-1h7.616v1H9.192v2.984l1.424 2.862v1H7.308v4.27zM15.73 7.27Q15 6.538 15 5.5t.73-1.77T17.5 3t1.77.73T20 5.5t-.73 1.77T17.5 8t-1.77-.73M13.043 6H3V5h10.042q-.011.116-.026.238q-.016.12-.016.242q0 .14.016.262q.015.122.026.257m-.6 13v-1H20V9.21q.292-.18.542-.387T21 8.346V19z");
}

</style>
