<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y6gtys2su.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1536,"height":1792};
const content = `<path class="y6gtys2su"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:paypal" /></template>
