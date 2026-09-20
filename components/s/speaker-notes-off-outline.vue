<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lfwe9vbyb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:speaker-notes-off-outline" /></template>
<style>
.lfwe9vbyb {
  fill: currentColor;
  d: path("M6.615 13.549q-.23-.22-.23-.549t.23-.549t.539-.22t.54.22t.229.549t-.23.549t-.54.22q-.309 0-.538-.22M19.7 16.966L18.85 16h.535q.269 0 .442-.173t.173-.442V4.615q0-.269-.173-.442T19.385 4H6.85l-1-1h13.535q.69 0 1.153.463T21 4.616v10.769q0 .65-.363 1.041q-.362.391-.937.54M13.35 10.5l-1-1h5.15v1zm6.92 11.185L15.572 17H6.077L3 20.077V4.416L1.008 2.423l.707-.707l19.262 19.261zM6.614 10.549q-.23-.22-.23-.549t.23-.549t.539-.22t.54.22t.229.549t-.23.549t-.54.22q-.309 0-.538-.22M10.35 7.5l-.408-.408V6.5H17.5v1zM4 5.416v12.228L5.65 16h8.935z");
}

</style>
