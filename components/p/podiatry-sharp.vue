<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ygn8-u9yi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:podiatry-sharp" /></template>
<style>
.ygn8-u9yi {
  fill: currentColor;
  d: path("m17.254 14.41l3.705-3.706l.714.713l-3.712 3.706zM2.75 18.788v-3.001q.914-.337 1.771-.76q.858-.423 1.621-1.03l1.174 1.317l.719-.72l-1.156-1.261q.142-.142.291-.272q.15-.13.292-.278l1.142 1.242l.725-.725l-1.34-1.41q.124-.153.233-.33q.109-.175.19-.38l1.486 1.55l.668-.666l-1.787-1.845l1.006-2.042l4.515-4.12l5.666 5.672l-8.908 9.06z");
}

</style>
