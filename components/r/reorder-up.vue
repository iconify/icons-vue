<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h8as2hbtw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h8as2hbtw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand:reorder-up" /></template>
