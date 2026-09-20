<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p7xcghbtx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="p7xcghbtx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:select-cursor" /></template>
