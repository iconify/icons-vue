<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vbw-5nbbu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vbw-5nbbu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:strava-statistics-light" /></template>
