<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ht_7bdhyg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:note-alt-rounded" /></template>
<style>
.ht_7bdhyg {
  fill: currentColor;
  d: path("M5.616 20q-.667 0-1.141-.475T4 18.386V5.615q0-.666.475-1.14T5.615 4h4.7q-.136-.766.367-1.383Q11.184 2 12.01 2t1.328.617T13.685 4h4.7q.666 0 1.14.475T20 5.615v12.77q0 .666-.475 1.14t-1.14.475zm6.922-15.77q.212-.213.212-.538t-.212-.537T12 2.942t-.537.213t-.213.537t.213.538t.537.212t.538-.212m-4.365 12h.296q.154 0 .297-.058q.144-.058.268-.183l5.682-5.631l-1.074-1.074l-5.63 5.631q-.131.131-.187.275t-.056.297v.34q0 .162.122.283q.12.12.282.12m7.089-6.418l.819-.831q.15-.15.15-.35t-.15-.35l-.362-.362q-.15-.15-.35-.15t-.35.15l-.83.82z");
}

</style>
