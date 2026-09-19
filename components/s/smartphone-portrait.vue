<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l314gsbcc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":304,"height":480};
const content = `<path class="l314gsbcc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:smartphone-portrait" /></template>
