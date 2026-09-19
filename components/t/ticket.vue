<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vp_aarktq.css';
import '../../css/u/uy9bf6bqn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="vp_aarktq"/><path class="uy9bf6bqn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="foundation:ticket" /></template>
