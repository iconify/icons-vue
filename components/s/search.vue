<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s3etm-s9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<path class="s3etm-s9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="map:search" /></template>
