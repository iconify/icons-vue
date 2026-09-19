<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/t/t2ouk1byg.css';
import '../../css/l/l0zoj3aiv.css';
import '../../css/p/p0b_9mvhd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="t2ouk1byg"/><path class="l0zoj3aiv"/><path class="p0b_9mvhd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-flat:mushroom" /></template>
