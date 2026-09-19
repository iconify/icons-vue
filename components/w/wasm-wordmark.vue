<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e73x-3b6j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="e73x-3b6j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:wasm-wordmark" /></template>
