<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h8x7bwbch.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="h8x7bwbch"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:random" /></template>
