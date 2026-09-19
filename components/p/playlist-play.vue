<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z8zb9mb9y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z8zb9mb9y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:playlist-play" /></template>
