<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/er5bmi5ai.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":1023};
const content = `<path class="er5bmi5ai"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:toothbrush" /></template>
