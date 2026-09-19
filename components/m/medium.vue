<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/l/l7z6dbf4g.css';
import '../../css/j/jfx8o0b0z.css';
import '../../css/o/oz-lqwbam.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><circle class="l7z6dbf4g"/><ellipse class="jfx8o0b0z"/><ellipse class="oz-lqwbam"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:medium" /></template>
