<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e140rv4yf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e140rv4yf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:text-justify" /></template>
