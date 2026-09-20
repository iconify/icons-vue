<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kt-r8b3tw.css';
import '../../css/c/ckmztbc7a.css';
import '../../css/c/cky9negol.css';
import '../../css/s/s5vh77buj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="kt-r8b3tw"/><linearGradient id="SVGUWtUKbEh" x1="157.99" x2="476.24" y1="811.473" y2="493.224" gradientTransform="translate(-8.065 -396.349)" gradientUnits="userSpaceOnUse"><stop offset="0" class="ckmztbc7a"/><stop offset=".994" class="cky9negol"/></linearGradient><path fill="url(#SVGUWtUKbEh)" class="s5vh77buj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:microsoft-to-do" /></template>
