<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rz6l8ac5v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rz6l8ac5v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:play-pause-fill-round" /></template>
