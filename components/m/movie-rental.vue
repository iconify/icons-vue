<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t_w102j1p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<path class="t_w102j1p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="map:movie-rental" /></template>
