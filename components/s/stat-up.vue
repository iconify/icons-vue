<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wv-10c8zx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wv-10c8zx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:stat-up" /></template>
