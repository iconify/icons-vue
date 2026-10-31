<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yd-1klc9r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yd-1klc9r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:pencil-alt-bulk-round" /></template>
