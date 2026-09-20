<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q0urbzbly.css';
import '../../css/y/y_s6t7b8x.css';
import '../../css/u/u11od-bgv.css';
import '../../css/f/fzy27luea.css';
import '../../css/c/cq9nz01qo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="q0urbzbly"/><path class="y_s6t7b8x"/><path class="u11od-bgv"/><path class="fzy27luea"/><path class="cq9nz01qo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:mini-qr" /></template>
