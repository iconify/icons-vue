<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fxgcv6b3c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":30};
const content = `<path class="fxgcv6b3c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wi:night-alt-thunderstorm" /></template>
