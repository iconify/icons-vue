<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b65qfabyr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b65qfabyr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:power-box" /></template>
