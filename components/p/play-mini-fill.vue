<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vnti9qbac.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vnti9qbac"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:play-mini-fill" /></template>
