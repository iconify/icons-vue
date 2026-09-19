<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/spvfrgbsk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":344,"height":480};
const content = `<path class="spvfrgbsk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:smartphone-code" /></template>
