<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ki3taftaq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":40,"height":24};
const content = `<path class="ki3taftaq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nrk:multiplier-2" /></template>
