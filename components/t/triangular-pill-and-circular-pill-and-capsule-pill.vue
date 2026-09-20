<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/weypos4si.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="weypos4si"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:triangular-pill-and-circular-pill-and-capsule-pill" /></template>
