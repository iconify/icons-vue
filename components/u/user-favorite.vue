<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g_nha4_pc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="g_nha4_pc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:user-favorite" /></template>
