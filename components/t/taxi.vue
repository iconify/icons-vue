<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tf53kacgl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="tf53kacgl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:taxi" /></template>
