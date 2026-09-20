<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yq8o9f3-q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yq8o9f3-q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:terminal-cursor" /></template>
