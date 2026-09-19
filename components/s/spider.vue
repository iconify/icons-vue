<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rv78ecc3b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rv78ecc3b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:spider" /></template>
