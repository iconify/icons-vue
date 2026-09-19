<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xgtg1ybgm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="xgtg1ybgm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:shield" /></template>
