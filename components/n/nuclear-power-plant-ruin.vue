<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mhfrgtbkm.css';
import '../../css/e/e6wn1qlca.css';
import '../../css/l/loz46zgag.css';
import '../../css/m/ml4n4-8gg.css';
import '../../css/j/jn8qy4bru.css';
import '../../css/v/vtk6uvxsm.css';
import '../../css/g/gdep6kbjz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="mhfrgtbkm"/><path class="e6wn1qlca"/><path class="loz46zgag"/><path class="ml4n4-8gg"/><g class="jn8qy4bru"><path class="vtk6uvxsm"/><path class="gdep6kbjz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:nuclear-power-plant-ruin" /></template>
