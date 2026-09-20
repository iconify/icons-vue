<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v1k5fg00x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":30};
const content = `<path class="v1k5fg00x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wi:sandstorm" /></template>
