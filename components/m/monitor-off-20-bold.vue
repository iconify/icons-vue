<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lznpb-b-w.css';
import '../../css/w/w0poz4bns.css';
import '../../css/n/n4zx3qb1w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="lznpb-b-w"/><path class="w0poz4bns"/><path class="n4zx3qb1w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:monitor-off-20-bold" /></template>
