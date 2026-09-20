<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wnbbg7bgq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wnbbg7bgq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:symbol" /></template>
