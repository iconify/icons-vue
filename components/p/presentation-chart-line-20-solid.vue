<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w-ztx0b_l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="w-ztx0b_l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:presentation-chart-line-20-solid" /></template>
