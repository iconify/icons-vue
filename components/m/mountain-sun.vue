<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tysrqtbnr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="tysrqtbnr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:mountain-sun" /></template>
