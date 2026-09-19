<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hshx60-si.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="hshx60-si"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:webgpu-wordmark" /></template>
