<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zepghmc3v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zepghmc3v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:sticker-line" /></template>
