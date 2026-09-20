<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ovul_dq1a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ovul_dq1a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:pixel-canoe-on-water" /></template>
