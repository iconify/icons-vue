<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/g/g79rgltqv.css';
import '../../css/i/i79d0rboe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":83,"height":82};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="g79rgltqv"/><path class="i79d0rboe"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:puzzle-piece" /></template>
