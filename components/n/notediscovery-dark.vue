<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qx32gdm7x.css';
import '../../css/k/kio5svbfy.css';
import '../../css/v/vk19fvz-k.css';
import '../../css/j/jigtxrbfx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<linearGradient id="SVGJ8jgDb0W" x1="18.3" x2="493.7" y1="18.3" y2="493.7" gradientUnits="userSpaceOnUse"><stop offset="0"/><stop offset="1" class="qx32gdm7x"/></linearGradient><path fill="url(#SVGJ8jgDb0W)" class="kio5svbfy"/><path class="vk19fvz-k"/><circle class="jigtxrbfx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:notediscovery-dark" /></template>
