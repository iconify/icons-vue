<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lxbw_dbuu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lxbw_dbuu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:yoga-half-moon-pose-1-bold" /></template>
