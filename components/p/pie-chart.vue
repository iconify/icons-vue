<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m5mqw_b-g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="m5mqw_b-g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="radix-icons:pie-chart" /></template>
