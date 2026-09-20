<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zh65d-5az.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zh65d-5az"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:transition-top" /></template>
