<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wi6522bgd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="wi6522bgd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:share-alt-square-solid" /></template>
