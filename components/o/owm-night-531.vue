<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jmvjp89df.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":30};
const content = `<path class="jmvjp89df"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wi:owm-night-531" /></template>
