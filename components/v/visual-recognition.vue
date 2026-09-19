<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ccqy6rbku.css';
import '../../css/v/vvwnsy9um.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<circle class="ccqy6rbku"/><path class="vvwnsy9um"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:visual-recognition" /></template>
