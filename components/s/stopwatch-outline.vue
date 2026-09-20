<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a3xbfpbxl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="a3xbfpbxl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:stopwatch-outline" /></template>
