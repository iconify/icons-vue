<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yyy2bx0hb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:sports-cricket" /></template>
<style>
.yyy2bx0hb {
  fill: currentColor;
  d: path("m14.308 14.046l-2.262 2.262q-.242.242-.546.242t-.546-.242l-8-7.962q-.243-.242-.243-.521t.243-.521l2.338-2.338q.242-.243.533-.243t.533.243l7.95 8.026q.242.242.242.527t-.242.527m4.292 7.262l-4.327-4.327l.708-.708l4.327 4.327zM16.544 7.456q-.813-.814-.813-1.956t.813-1.956t1.956-.813t1.956.813t.813 1.956t-.813 1.956t-1.956.813t-1.956-.813");
}

</style>
