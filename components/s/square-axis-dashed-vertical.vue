<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/epvlj5hbl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="epvlj5hbl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:square-axis-dashed-vertical" /></template>
