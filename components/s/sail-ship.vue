<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xz0hutb1x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="xz0hutb1x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:sail-ship" /></template>
