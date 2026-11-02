<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d11tu2hwl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d11tu2hwl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:za-sort-descending-letters-line" /></template>
