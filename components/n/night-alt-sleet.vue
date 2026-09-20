<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fdam__0oy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":30};
const content = `<path class="fdam__0oy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wi:night-alt-sleet" /></template>
