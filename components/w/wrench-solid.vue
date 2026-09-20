<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qbzck1ymf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qbzck1ymf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:wrench-solid" /></template>
