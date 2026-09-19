<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b5d3vjidn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b5d3vjidn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:shadcn-square" /></template>
