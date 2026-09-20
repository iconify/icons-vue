<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tnjapb-yg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="tnjapb-yg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:rail-metro-15" /></template>
