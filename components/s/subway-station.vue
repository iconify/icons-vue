<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/azaf2ubzu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<path class="azaf2ubzu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="map:subway-station" /></template>
