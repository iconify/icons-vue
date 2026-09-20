<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yrme0_b0x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yrme0_b0x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:tablecheck" /></template>
