<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o-s9c5bkm.css';
import '../../css/u/uyag2jl5g.css';
import '../../css/l/l4v9huevr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="o-s9c5bkm"/><path class="uyag2jl5g"/><path class="l4v9huevr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:solar-shading-20-bold" /></template>
