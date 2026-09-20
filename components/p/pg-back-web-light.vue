<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j30e7ybjx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="j30e7ybjx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:pg-back-web-light" /></template>
