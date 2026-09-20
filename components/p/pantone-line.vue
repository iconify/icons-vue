<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y2e20tbfc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y2e20tbfc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:pantone-line" /></template>
