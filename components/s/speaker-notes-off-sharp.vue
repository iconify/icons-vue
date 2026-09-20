<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b7seh8b7w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:speaker-notes-off-sharp" /></template>
<style>
.b7seh8b7w {
  fill: currentColor;
  d: path("M20.27 21.685L15.572 17H6.077L3 20.077V4.116h1.116l6.653 6.653H9.354L1.008 2.423l.707-.707l19.262 19.261zm-.57-4.72L13.292 10.5H17.5v-1h-5.208l-1.942-2h7.15v-1H9.942v.592L5.85 3H21v13.966zM7.693 13.54q.23-.23.23-.54t-.23-.54t-.54-.23t-.538.23t-.23.54t.23.54t.539.23t.54-.23m0-3q.229-.23.229-.54t-.23-.54t-.54-.23t-.538.23t-.23.54t.23.54t.539.23t.54-.23");
}

</style>
