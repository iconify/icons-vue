<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w5zqg0bvt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="w5zqg0bvt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:screen-1" /></template>
