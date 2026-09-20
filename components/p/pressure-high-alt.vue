<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p21c9ubxg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="p21c9ubxg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="meteocons:pressure-high-alt" /></template>
