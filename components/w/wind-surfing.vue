<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e9oun0bdp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<path class="e9oun0bdp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:wind-surfing" /></template>
