<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m0-p-2upt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="m0-p-2upt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="raphael:sticker" /></template>
