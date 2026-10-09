<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v7tm0ry1a.css';
import '../../css/i/ivgem8b_w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="v7tm0ry1a"/><path class="ivgem8b_w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:supply-chain-20" /></template>
