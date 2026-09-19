<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/buijfg4ca.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="buijfg4ca"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:snooze-outline" /></template>
