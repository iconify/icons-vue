<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l9revib3y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="l9revib3y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:send-backward-bold" /></template>
