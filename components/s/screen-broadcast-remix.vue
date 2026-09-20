<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vod3zxb3c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="vod3zxb3c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:screen-broadcast-remix" /></template>
