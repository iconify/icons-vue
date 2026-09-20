<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h92d--bgm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":30};
const content = `<path class="h92d--bgm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wi:moonrise" /></template>
