<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fpz7tqcjq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<path class="fpz7tqcjq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="map:police" /></template>
