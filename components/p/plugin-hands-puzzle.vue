<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kocj6_b-l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kocj6_b-l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand:plugin-hands-puzzle" /></template>
