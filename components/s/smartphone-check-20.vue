<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w9mf9qlbg.css';
import '../../css/w/wj8c8qbtx.css';
import '../../css/q/qh3-d7bck.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="w9mf9qlbg"/><path class="wj8c8qbtx"/><path class="qh3-d7bck"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:smartphone-check-20" /></template>
