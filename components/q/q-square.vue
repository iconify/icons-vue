<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lyp-bobqo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1792,"height":1792};
const content = `<path class="lyp-bobqo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vs:q-square" /></template>
