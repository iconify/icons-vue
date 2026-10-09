<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yqwy2slfp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="yqwy2slfp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:signal-none-48" /></template>
