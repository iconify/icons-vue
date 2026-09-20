<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ybsh2wbgj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ybsh2wbgj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:voice-id" /></template>
