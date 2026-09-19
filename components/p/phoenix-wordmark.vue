<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w456yoqax.css';
import '../../css/d/d_jwqly5w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="w456yoqax"/><path class="d_jwqly5w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:phoenix-wordmark" /></template>
