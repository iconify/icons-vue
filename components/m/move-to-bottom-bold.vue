<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u7o2f7z5o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u7o2f7z5o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:move-to-bottom-bold" /></template>
