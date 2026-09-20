<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p0vnysy8k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p0vnysy8k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:matrix" /></template>
