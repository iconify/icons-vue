<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o9ex4pjbc.css';
import '../../css/r/rvb6adcua.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o9ex4pjbc"/><path class="rvb6adcua"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand:shopping-basket-like" /></template>
