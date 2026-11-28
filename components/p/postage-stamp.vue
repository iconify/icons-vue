<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a7d8g7bua.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="a7d8g7bua"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:postage-stamp" /></template>
