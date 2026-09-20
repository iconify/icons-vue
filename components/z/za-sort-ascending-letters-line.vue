<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zyv0nyqej.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zyv0nyqej"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:za-sort-ascending-letters-line" /></template>
