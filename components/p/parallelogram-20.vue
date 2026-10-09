<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lhnu4y6xm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="lhnu4y6xm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:parallelogram-20" /></template>
