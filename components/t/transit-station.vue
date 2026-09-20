<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yqc8g_bho.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<path class="yqc8g_bho"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="map:transit-station" /></template>
