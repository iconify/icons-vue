<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wb4qxybou.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wb4qxybou"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:mic-2-line" /></template>
