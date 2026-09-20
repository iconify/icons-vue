<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w10xf1pso.css';
import '../../css/m/mw546i83n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="w10xf1pso"/><path class="mw546i83n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:tinfoil-dark" /></template>
