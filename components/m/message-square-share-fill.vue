<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ynm3t7yqr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ynm3t7yqr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:message-square-share-fill" /></template>
