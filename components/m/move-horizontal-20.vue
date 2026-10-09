<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w5zpafb6d.css';
import '../../css/y/y7i36sqce.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="w5zpafb6d"/><path class="y7i36sqce"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:move-horizontal-20" /></template>
