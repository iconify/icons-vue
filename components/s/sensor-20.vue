<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uyzben50c.css';
import '../../css/y/ylpvizbha.css';
import '../../css/a/atgoxpbsa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="uyzben50c"/><path class="ylpvizbha"/><path class="atgoxpbsa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:sensor-20" /></template>
