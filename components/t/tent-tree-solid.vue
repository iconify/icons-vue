<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o1y5m5elh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o1y5m5elh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:tent-tree-solid" /></template>
