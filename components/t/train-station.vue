<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vnjk4qv4f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<path class="vnjk4qv4f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="map:train-station" /></template>
