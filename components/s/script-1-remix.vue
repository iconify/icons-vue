<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ydwy7o8kw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ydwy7o8kw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:script-1-remix" /></template>
