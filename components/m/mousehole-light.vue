<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zh-l097mh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zh-l097mh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:mousehole-light" /></template>
