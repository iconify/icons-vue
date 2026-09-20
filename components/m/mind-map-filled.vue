<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y5gj8kbmf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y5gj8kbmf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:mind-map-filled" /></template>
