<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d00ah8b2d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":30};
const content = `<path class="d00ah8b2d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wi:owm-711" /></template>
