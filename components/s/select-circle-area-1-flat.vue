<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qwkm3t4kl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="qwkm3t4kl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-color:select-circle-area-1-flat" /></template>
