<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kh7i2l54q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":30};
const content = `<path class="kh7i2l54q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wi:night-alt-snow-thunderstorm" /></template>
