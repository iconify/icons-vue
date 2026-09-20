<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gr_iggcno.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":30};
const content = `<path class="gr_iggcno"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wi:owm-night-300" /></template>
