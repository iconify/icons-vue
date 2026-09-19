<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l_8xx_b4w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l_8xx_b4w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:maps-arrow-xmark" /></template>
