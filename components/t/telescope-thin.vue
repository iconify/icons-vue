<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wuxazfbwj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="wuxazfbwj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:telescope-thin" /></template>
