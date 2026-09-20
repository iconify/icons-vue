<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wbd42ygua.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="wbd42ygua"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump-color:tiktok-flat" /></template>
