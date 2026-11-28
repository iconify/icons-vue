<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eo8_tu72j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eo8_tu72j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:wifi-refresh" /></template>
