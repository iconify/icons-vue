<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qp__ydbjh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="qp__ydbjh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:zoo-uppercase" /></template>
