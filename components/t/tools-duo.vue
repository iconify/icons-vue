<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/o/oyxvwvb9z.css';
import '../../css/v/v2-sg-bdy.css';
import '../../css/n/nxpruiwiw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="oyxvwvb9z"/><path class="v2-sg-bdy"/><path class="nxpruiwiw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:tools-duo" /></template>
