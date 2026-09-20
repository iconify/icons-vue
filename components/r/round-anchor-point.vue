<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cn9lbrbjn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="cn9lbrbjn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:round-anchor-point" /></template>
