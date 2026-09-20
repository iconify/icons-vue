<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jsxu6h-uf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jsxu6h-uf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:rahoot-light" /></template>
