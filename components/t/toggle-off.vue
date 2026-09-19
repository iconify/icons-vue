<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vws3t-8ts.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":1280};
const content = `<path class="vws3t-8ts"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:toggle-off" /></template>
