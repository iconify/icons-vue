<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vckumgsmf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vckumgsmf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:paper-cut-vertical" /></template>
