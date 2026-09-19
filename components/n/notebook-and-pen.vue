<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wc9ys4ivd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="wc9ys4ivd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:notebook-and-pen" /></template>
