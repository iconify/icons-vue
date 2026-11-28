<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qmwgk_bil.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qmwgk_bil"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:square-bookmark-solid" /></template>
