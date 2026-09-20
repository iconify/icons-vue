<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yey0n_erf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<path class="yey0n_erf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="map:roofing-contractor" /></template>
