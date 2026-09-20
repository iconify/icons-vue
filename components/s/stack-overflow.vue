<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/njuu40vwh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="njuu40vwh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:stack-overflow" /></template>
