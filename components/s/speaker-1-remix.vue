<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wy6cmybio.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="wy6cmybio"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:speaker-1-remix" /></template>
