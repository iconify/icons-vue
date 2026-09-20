<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/snoq0vy-t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="snoq0vy-t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:no-wiki-text" /></template>
