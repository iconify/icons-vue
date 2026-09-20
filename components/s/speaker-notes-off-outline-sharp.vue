<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fyu_c9bsv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:speaker-notes-off-outline-sharp" /></template>
<style>
.fyu_c9bsv {
  fill: currentColor;
  d: path("M6.615 13.549q-.23-.22-.23-.549t.23-.549t.539-.22t.54.22t.229.549t-.23.549t-.54.22q-.309 0-.538-.22M19.7 16.966L18.85 16H20V4H6.85l-1-1H21v13.966zM13.35 10.5l-1-1h5.15v1zm6.92 11.185L15.572 17H6.077L3 20.077V4.416L1.008 2.423l.707-.707l19.262 19.261zM6.614 10.549q-.23-.22-.23-.549t.23-.549t.539-.22t.54.22t.229.549t-.23.549t-.54.22q-.309 0-.538-.22M10.35 7.5l-.408-.408V6.5H17.5v1zM4 5.416v12.228L5.65 16h8.935z");
}

</style>
