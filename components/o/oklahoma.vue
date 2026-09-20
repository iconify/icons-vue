<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ulbjf7bty.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ulbjf7bty"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:oklahoma" /></template>
