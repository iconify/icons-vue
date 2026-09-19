<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mhck25btm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mhck25btm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:pizza-slice" /></template>
