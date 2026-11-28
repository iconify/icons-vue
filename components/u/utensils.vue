<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ohq7uzbwc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ohq7uzbwc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:utensils" /></template>
