<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fy3fim5nn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fy3fim5nn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:x-circle" /></template>
