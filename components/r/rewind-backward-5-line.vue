<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uar_8mb5g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uar_8mb5g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:rewind-backward-5-line" /></template>
