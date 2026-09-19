<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mht05k55h.css';
import '../../css/d/ds9m6_b0q.css';
import '../../css/f/fszk4qb6g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="mht05k55h"/><path class="ds9m6_b0q"/><path class="fszk4qb6g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:wind-gusts" /></template>
