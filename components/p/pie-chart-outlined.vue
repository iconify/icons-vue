<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oe_m0xv8t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="oe_m0xv8t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:pie-chart-outlined" /></template>
