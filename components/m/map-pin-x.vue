<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yau77fbid.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yau77fbid"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:map-pin-x" /></template>
