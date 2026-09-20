<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x-r60-bqt.css';
import '../../css/b/bkk1zoblz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="x-r60-bqt"/><path class="bkk1zoblz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:map-navigation-pin-location-1" /></template>
