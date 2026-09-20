<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jhum8un3s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jhum8un3s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand:saving-bull-market" /></template>
