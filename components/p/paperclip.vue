<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wlxh2hoir.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="wlxh2hoir"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="foundation:paperclip" /></template>
