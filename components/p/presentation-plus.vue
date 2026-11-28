<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pgrk8c2ry.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pgrk8c2ry"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:presentation-plus" /></template>
