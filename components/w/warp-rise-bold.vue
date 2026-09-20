<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ytwz4pbpy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ytwz4pbpy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:warp-rise-bold" /></template>
