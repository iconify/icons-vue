<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zqnvo5brk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zqnvo5brk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:train-fill" /></template>
