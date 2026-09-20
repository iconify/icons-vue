<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fxy3dwbbq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="fxy3dwbbq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:photography-retouch-wand" /></template>
