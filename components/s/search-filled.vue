<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vebhmnb-j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vebhmnb-j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="weui:search-filled" /></template>
