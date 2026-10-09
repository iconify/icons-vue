<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cc7985b_u.css';
import '../../css/v/v3ruwkbvo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="cc7985b_u"/><path class="v3ruwkbvo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:scope-3-20-bold" /></template>
