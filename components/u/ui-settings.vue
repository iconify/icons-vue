<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yrt28lblq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="yrt28lblq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:ui-settings" /></template>
