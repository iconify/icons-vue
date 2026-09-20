<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wnb03vb7m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="wnb03vb7m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:trend-upward-circle" /></template>
