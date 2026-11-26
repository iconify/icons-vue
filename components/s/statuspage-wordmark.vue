<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dr24xacoy.css';
import '../../css/e/etdr-zbkq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="dr24xacoy"/><path class="etdr-zbkq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:statuspage-wordmark" /></template>
