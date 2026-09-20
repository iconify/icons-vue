<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/arxuswbpy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="arxuswbpy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-lab:towel-rack" /></template>
