<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s48y1gbzv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s48y1gbzv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:screen-share-check" /></template>
