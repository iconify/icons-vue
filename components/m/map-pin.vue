<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k2m49ccqe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<path class="k2m49ccqe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="map:map-pin" /></template>
