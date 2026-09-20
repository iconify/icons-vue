<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hh5krp3xg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="hh5krp3xg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:pickup-truck-under-wrench" /></template>
