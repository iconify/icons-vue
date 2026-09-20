<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/u/usngqit7o.css';
import '../../css/k/kyjj1r1_l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":40,"height":40};
const content = `<g class="ft5dv1b6b"><path class="usngqit7o"/><path clip-rule="evenodd" class="kyjj1r1_l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:perspective-dark" /></template>
