<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f5tdmyt-g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f5tdmyt-g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mono-icons:reorder" /></template>
