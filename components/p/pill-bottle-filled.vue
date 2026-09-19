<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zr54h2ycg.css';
import '../../css/e/e4rr4w_hj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<rect class="zr54h2ycg"/><path class="e4rr4w_hj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:pill-bottle-filled" /></template>
