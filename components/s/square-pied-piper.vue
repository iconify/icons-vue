<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q3cu2bbmq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="q3cu2bbmq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:square-pied-piper" /></template>
