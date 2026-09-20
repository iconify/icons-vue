<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jtl3x1bac.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="jtl3x1bac"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:pickup-truck-and-tag" /></template>
