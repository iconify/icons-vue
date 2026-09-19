<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l5wakvbmm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":447,"height":512};
const content = `<path class="l5wakvbmm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:rubygems" /></template>
