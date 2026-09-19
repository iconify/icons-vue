<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i84evwbcm.css';
import '../../css/z/zej4k5jhq.css';
import '../../css/q/q9ug-zblj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="i84evwbcm"/><path class="zej4k5jhq"/><path class="q9ug-zblj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:status-change" /></template>
