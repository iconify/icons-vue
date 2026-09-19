<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/co8z4ybbz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="co8z4ybbz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:plug-filled" /></template>
