<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q1lc-wt4o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="q1lc-wt4o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:pixel-transit-vehicle-on-railway-track" /></template>
