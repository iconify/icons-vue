<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kpm1h9bjw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":30};
const content = `<path class="kpm1h9bjw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wi:time-3" /></template>
