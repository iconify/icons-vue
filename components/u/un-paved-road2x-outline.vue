<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yszikpxfw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="yszikpxfw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:un-paved-road2x-outline" /></template>
