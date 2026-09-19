<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g3q_3l9wz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="g3q_3l9wz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:multiple-windows" /></template>
