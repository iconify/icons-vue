<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o7rm7zgux.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o7rm7zgux"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:presentation-chart-line" /></template>
