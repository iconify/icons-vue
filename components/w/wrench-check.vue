<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/ps8-4yx3u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ps8-4yx3u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:wrench-check" /></template>
