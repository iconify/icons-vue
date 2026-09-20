<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c2g7scb2e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="c2g7scb2e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:toilet-man-solid" /></template>
