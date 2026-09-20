<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u7u9cyb1w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="u7u9cyb1w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:page-break-solid" /></template>
