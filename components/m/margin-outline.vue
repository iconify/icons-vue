<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fwnf31een"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:margin-outline" /></template>
<style>
.fwnf31een {
  fill: currentColor;
  d: path("M5.616 20q-.691 0-1.153-.462T4 18.384V5.616q0-.691.463-1.153T5.616 4h12.769q.69 0 1.153.463T20 5.616v12.769q0 .69-.462 1.153T18.384 20zm0-1h12.769q.23 0 .423-.192t.192-.424V5.616q0-.231-.192-.424T18.384 5H5.616q-.231 0-.424.192T5 5.616v12.769q0 .23.192.423t.423.192M5 5v14zm3.655 3.674q.23-.23.23-.54q0-.309-.23-.539t-.54-.23t-.539.23t-.23.54t.23.539t.54.23t.539-.23m3.345.23q.31 0 .54-.23t.23-.54t-.23-.539t-.54-.23t-.54.23t-.23.54t.23.539t.54.23m4.424-.23q.23-.23.23-.54q0-.309-.23-.539t-.54-.23t-.539.23t-.23.54t.23.539t.54.23t.539-.23m0 3.866q.23-.23.23-.54t-.23-.54t-.54-.23t-.539.23t-.23.54t.23.54t.54.23t.539-.23M12 12.77q.31 0 .54-.23t.23-.54t-.23-.54t-.54-.23t-.54.23t-.23.54t.23.54t.54.23m-3.345-.23q.23-.23.23-.54t-.23-.54t-.54-.23t-.539.23t-.23.54t.23.54t.54.23t.539-.23");
}

</style>
