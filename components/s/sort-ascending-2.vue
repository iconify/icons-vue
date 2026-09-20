<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fy7pxvbgg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fy7pxvbgg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:sort-ascending-2" /></template>
