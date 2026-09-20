<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vbl_ijbzj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":30};
const content = `<path class="vbl_ijbzj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wi:owm-night-903" /></template>
