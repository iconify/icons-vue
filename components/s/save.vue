<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ub3z3pbln.css';
import '../../css/f/fe-h--bgr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ub3z3pbln"/><circle class="fe-h--bgr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:save" /></template>
