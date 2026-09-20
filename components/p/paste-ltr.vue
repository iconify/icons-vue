<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ueb6e8bmp.css';
import '../../css/i/i0qqi58le.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ueb6e8bmp"/><path class="i0qqi58le"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:paste-ltr" /></template>
