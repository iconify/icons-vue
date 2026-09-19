<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u2io2hbsl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="u2io2hbsl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:window-minimize" /></template>
