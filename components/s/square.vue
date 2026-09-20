<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cnicabbgd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<path class="cnicabbgd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="map:square" /></template>
