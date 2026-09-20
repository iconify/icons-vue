<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j4wqo7b8d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j4wqo7b8d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:pyramid-chart-light" /></template>
