<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uxfnk_byo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="uxfnk_byo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:matroska" /></template>
