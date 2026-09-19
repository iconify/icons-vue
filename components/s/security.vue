<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c5t1omb0s.css';
import '../../css/e/ey3vbs2kb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="c5t1omb0s"/><path class="ey3vbs2kb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:security" /></template>
