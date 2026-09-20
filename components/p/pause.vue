<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/imx0tq8pe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="imx0tq8pe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zondicons:pause" /></template>
