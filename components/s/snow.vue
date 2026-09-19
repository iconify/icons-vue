<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/q/qauc5-naj.css';
import '../../css/m/m4qc6k9qt.css';
import '../../css/k/ktk0lz7oj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="qauc5-naj"/><path class="m4qc6k9qt"/><path class="ktk0lz7oj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:snow" /></template>
