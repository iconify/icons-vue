<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q23lrv8wj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="q23lrv8wj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:map-outline" /></template>
