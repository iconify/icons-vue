<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g8hg8vs1s.css';
import '../../css/f/ftbdi3bme.css';
import '../../css/v/v_xkw1bvd.css';
import '../../css/k/k5tg0g4zb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<linearGradient id="SVGkeTD6yDv" x1="73.5" x2="1353.5" y1="-334.5" y2="-334.5" gradientTransform="matrix(.4 0 0 -.4 -29.4 122.2)" gradientUnits="userSpaceOnUse"><stop offset="0" class="g8hg8vs1s"/><stop offset="1" class="ftbdi3bme"/></linearGradient><path fill="url(#SVGkeTD6yDv)" class="v_xkw1bvd"/><path class="k5tg0g4zb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:planning-center-giving" /></template>
