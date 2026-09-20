<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tx5a0xb9d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":30};
const content = `<path class="tx5a0xb9d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wi:night-snow-thunderstorm" /></template>
