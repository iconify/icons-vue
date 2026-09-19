<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/u/u-tqjdofv.css';
import '../../css/m/m2kr2vb1b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<g class="cuyn6tgcc"><path class="u-tqjdofv"/><path class="m2kr2vb1b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="foundation:social-instagram" /></template>
