<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h-_tg5nyk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h-_tg5nyk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:pie-chart-25" /></template>
