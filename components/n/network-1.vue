<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cmvd4q53w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="cmvd4q53w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:network-1" /></template>
