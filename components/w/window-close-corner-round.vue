<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x7kyxznsn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x7kyxznsn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:window-close-corner-round" /></template>
