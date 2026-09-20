<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cmzdm6ops.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="cmzdm6ops"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="subway:tool-box-1" /></template>
