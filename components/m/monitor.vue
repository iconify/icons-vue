<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w_-r3se3i.css';
import '../../css/j/juudgbbnj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="w_-r3se3i"/><path class="juudgbbnj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:monitor" /></template>
