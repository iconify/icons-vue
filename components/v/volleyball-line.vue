<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rhqxtlbfc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rhqxtlbfc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:volleyball-line" /></template>
