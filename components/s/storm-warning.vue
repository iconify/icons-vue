<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eb4jft9ev.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":30};
const content = `<path class="eb4jft9ev"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wi:storm-warning" /></template>
