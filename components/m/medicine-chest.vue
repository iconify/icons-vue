<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/o/o_x_9py4c.css';
import '../../css/f/fcpg31afm.css';
import '../../css/l/lx95c5pyb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="ft5dv1b6b"><rect class="o_x_9py4c"/><path class="fcpg31afm"/><path class="lx95c5pyb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:medicine-chest" /></template>
