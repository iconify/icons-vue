<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zwv2d3bhh.css';
import '../../css/l/lrqqa_b2z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zwv2d3bhh"/><path class="lrqqa_b2z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:vpn-sentinel-dark" /></template>
