<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hnkzp_giv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="hnkzp_giv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:pi-symbol-circle-solid" /></template>
