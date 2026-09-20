<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i9tipdjsy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="i9tipdjsy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:round-anchor-point-solid" /></template>
