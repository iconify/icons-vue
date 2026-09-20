<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xg7c7ibcj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xg7c7ibcj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:seed-off-outline" /></template>
