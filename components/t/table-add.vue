<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xn9sui-lh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xn9sui-lh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:table-add" /></template>
