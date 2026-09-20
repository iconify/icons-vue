<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uqgpm_b_z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="uqgpm_b_z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:travel-map-flag-navigation-map-maps-flag-gps-location-destination-goal" /></template>
