<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mxptukb2q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mxptukb2q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:trapezoid" /></template>
