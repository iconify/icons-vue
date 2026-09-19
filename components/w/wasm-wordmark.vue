<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nqpr9y_fs.css';
import '../../css/y/ytq_a7bwt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="nqpr9y_fs"/><path class="ytq_a7bwt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:wasm-wordmark" /></template>
