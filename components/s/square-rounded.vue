<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nh-c4bb6i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<path class="nh-c4bb6i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="map:square-rounded" /></template>
