<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tf47s3b2g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="tf47s3b2g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:wind-48-bold" /></template>
