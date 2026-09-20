<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lg3i-ab3c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<path class="lg3i-ab3c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="map:movie-theater" /></template>
