<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xw1_x9b1z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":69,"height":26};
const content = `<path class="xw1_x9b1z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:wordmark-gather-26" /></template>
