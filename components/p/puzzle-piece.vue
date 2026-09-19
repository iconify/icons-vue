<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zlfijw3hs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":456};
const content = `<path class="zlfijw3hs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:puzzle-piece" /></template>
