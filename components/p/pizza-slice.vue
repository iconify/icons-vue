<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/e/e6zn6abhh.css';
import '../../css/q/q_f8gu14x.css';
import '../../css/g/gcioct8bz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><circle class="e6zn6abhh"/><path class="q_f8gu14x"/><path class="gcioct8bz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:pizza-slice" /></template>
