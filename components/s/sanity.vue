<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ax79bxbvg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ax79bxbvg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxl:sanity" /></template>
