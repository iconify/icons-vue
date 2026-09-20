<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qsww-ujmb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<path class="qsww-ujmb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="map:wheelchair" /></template>
