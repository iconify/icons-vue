<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wkcj9sbjs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wkcj9sbjs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:rewind-backward-square-15-line" /></template>
