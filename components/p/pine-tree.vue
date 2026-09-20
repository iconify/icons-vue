<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yl2-b5b0s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yl2-b5b0s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:pine-tree" /></template>
