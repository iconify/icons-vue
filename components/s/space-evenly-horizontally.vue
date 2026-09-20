<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iy0s6l-yp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="iy0s6l-yp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="radix-icons:space-evenly-horizontally" /></template>
