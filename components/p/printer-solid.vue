<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dsdmhbcob.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="dsdmhbcob"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="rivet-icons:printer-solid" /></template>
