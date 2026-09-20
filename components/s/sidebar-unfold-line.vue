<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eh7qx1bct.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eh7qx1bct"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:sidebar-unfold-line" /></template>
