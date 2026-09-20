<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vx3-z3b_q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="vx3-z3b_q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:wpexplorer" /></template>
