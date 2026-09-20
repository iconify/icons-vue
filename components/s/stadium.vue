<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t6byiab5n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<path class="t6byiab5n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="map:stadium" /></template>
