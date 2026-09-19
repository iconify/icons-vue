<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zwx_s704a.css';
import '../../css/q/qwe3y-4yj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="zwx_s704a"/><path class="qwe3y-4yj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:non-certified" /></template>
