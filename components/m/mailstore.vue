<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lcrl3bcgy.css';
import '../../css/i/iek9glb2w.css';
import '../../css/s/sij7iobyd.css';
import '../../css/r/rjboz-k8p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<linearGradient id="SVGt7wfBesf" x1="389.8" x2="81.5" y1="426.2" y2="34.2" gradientUnits="userSpaceOnUse"><stop offset="0" class="lcrl3bcgy"/><stop offset="1" class="iek9glb2w"/></linearGradient><path fill="url(#SVGt7wfBesf)" class="sij7iobyd"/><path class="rjboz-k8p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:mailstore" /></template>
