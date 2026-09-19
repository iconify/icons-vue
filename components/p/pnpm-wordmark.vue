<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sz4j5z9qi.css';
import '../../css/g/g878ilbyw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="sz4j5z9qi"/><path class="g878ilbyw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:pnpm-wordmark" /></template>
