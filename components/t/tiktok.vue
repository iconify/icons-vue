<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uiv8dcbcp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uiv8dcbcp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:tiktok" /></template>
