<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/umbp655yz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="umbp655yz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:map2" /></template>
