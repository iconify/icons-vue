<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/up8o3o55e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="up8o3o55e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:vomiting-24px" /></template>
