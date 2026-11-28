<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wc5w5cbbq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wc5w5cbbq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:sailboat" /></template>
