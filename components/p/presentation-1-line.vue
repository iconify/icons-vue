<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/axr0p6pmp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="axr0p6pmp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:presentation-1-line" /></template>
