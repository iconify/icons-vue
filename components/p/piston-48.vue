<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sy4vy0gsk.css';
import '../../css/u/uy2o04bub.css';
import '../../css/m/mbusswbar.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="sy4vy0gsk"/><path class="uy2o04bub"/><path class="mbusswbar"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:piston-48" /></template>
