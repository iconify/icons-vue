<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qi0wcie-m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qi0wcie-m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="subway:round-arrow-1" /></template>
