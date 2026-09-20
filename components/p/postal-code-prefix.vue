<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oii_trd6d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<path class="oii_trd6d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="map:postal-code-prefix" /></template>
