<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sd0v0ry5k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sd0v0ry5k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:waterfall-down-03" /></template>
