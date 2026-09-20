<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/obm3mkxem.css';
import '../../css/v/vw1b76hol.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="obm3mkxem"/><path class="vw1b76hol"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:map-navigation-pin-location-2" /></template>
