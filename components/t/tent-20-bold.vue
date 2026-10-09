<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g8gmoubzb.css';
import '../../css/o/oji4_ybzh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="g8gmoubzb"/><path class="oji4_ybzh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:tent-20-bold" /></template>
