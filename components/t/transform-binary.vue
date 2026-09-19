<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e7ik_xtrn.css';
import '../../css/w/wx-066bcp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="e7ik_xtrn"/><path class="wx-066bcp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:transform-binary" /></template>
