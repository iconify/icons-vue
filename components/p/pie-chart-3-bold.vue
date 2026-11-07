<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c_t-l-btv.css';
import '../../css/h/h6g7afq-c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c_t-l-btv"/><path class="h6g7afq-c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:pie-chart-3-bold" /></template>
