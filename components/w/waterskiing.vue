<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qd196f25w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<path class="qd196f25w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="map:waterskiing" /></template>
