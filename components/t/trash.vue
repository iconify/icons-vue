<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uqa_y83hy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uqa_y83hy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:trash" /></template>
