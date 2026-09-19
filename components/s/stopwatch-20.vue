<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tbe7n819p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="tbe7n819p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:stopwatch-20" /></template>
