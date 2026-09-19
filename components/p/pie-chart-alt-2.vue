<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/twbo-2bwl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b twbo-2bwl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:pie-chart-alt-2" /></template>
