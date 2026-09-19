<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e-5vzwbzx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":376,"height":384};
const content = `<path class="e-5vzwbzx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:search" /></template>
