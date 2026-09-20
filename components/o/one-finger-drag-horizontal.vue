<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s00ripn2b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="s00ripn2b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:one-finger-drag-horizontal" /></template>
