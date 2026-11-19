<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r7cs0_jfl.css';
import '../../css/e/ee7zd4bqr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="r7cs0_jfl"/><path class="ee7zd4bqr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:qwen-wordmark" /></template>
