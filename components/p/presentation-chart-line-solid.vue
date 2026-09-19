<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3x8cdl_s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="v3x8cdl_s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:presentation-chart-line-solid" /></template>
