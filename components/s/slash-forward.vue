<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cnol5tb1q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":21,"height":21};
const content = `<path class="cnol5tb1q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="system-uicons:slash-forward" /></template>
