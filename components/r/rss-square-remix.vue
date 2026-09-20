<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oxhzombuv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="oxhzombuv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:rss-square-remix" /></template>
