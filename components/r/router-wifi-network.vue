<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h01tyzbfu.css';
import '../../css/s/s42rpkduo.css';
import '../../css/w/wze762b-p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<g class="h01tyzbfu"><path class="s42rpkduo"/><path class="wze762b-p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:router-wifi-network" /></template>
