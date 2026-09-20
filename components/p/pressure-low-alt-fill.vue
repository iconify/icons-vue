<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k_nyj5beu.css';
import '../../css/h/hwnz52b0q.css';
import '../../css/q/q700p9b8s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<defs><linearGradient id="SVGIh3X4d1V" x1="184.3" x2="275.4" y1="192.2" y2="349.9" gradientUnits="userSpaceOnUse"><stop offset="0" class="k_nyj5beu"/><stop offset=".5" class="k_nyj5beu"/><stop offset="1" class="hwnz52b0q"/></linearGradient></defs><path fill="url(#SVGIh3X4d1V)" class="q700p9b8s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="meteocons:pressure-low-alt-fill" /></template>
