<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/ds_tcibbp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ds_tcibbp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:map-navigation-pin-location-trip" /></template>
