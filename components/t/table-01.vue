<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ys_306b9f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ys_306b9f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:table-01" /></template>
