<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/ji-p01brs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":40,"height":24};
const content = `<path class="ji-p01brs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nrk:multiplier-1-25" /></template>
