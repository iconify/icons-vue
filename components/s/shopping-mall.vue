<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d-3qr5bej.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<path class="d-3qr5bej"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="map:shopping-mall" /></template>
