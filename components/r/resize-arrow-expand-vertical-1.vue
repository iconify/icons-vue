<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jr-9tjbeb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jr-9tjbeb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand:resize-arrow-expand-vertical-1" /></template>
