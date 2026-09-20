<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y1hdy1ggy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y1hdy1ggy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:play-protected-content" /></template>
