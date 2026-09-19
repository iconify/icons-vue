<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gm8kqfbpa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":320,"height":512};
const content = `<path class="gm8kqfbpa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:temperature-empty" /></template>
