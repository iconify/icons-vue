<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k2a-x9sbe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k2a-x9sbe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:table-cells-split-fill-round" /></template>
