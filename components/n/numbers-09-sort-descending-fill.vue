<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ua5uh7bgc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ua5uh7bgc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:numbers-09-sort-descending-fill" /></template>
