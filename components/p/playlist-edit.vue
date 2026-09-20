<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ev7yxpbst.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ev7yxpbst"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:playlist-edit" /></template>
