<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y3sfconby.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y3sfconby"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:menu-bulk-round" /></template>
