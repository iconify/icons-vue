<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ulaa0sbdf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ulaa0sbdf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:pause-square-solid" /></template>
