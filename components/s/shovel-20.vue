<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q1pekhtvh.css';
import '../../css/g/gipfg7brd.css';
import '../../css/l/le6qx_s4l.css';
import '../../css/m/mpz045b2n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="q1pekhtvh"/><path class="gipfg7brd"/><path class="le6qx_s4l"/><path class="mpz045b2n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:shovel-20" /></template>
