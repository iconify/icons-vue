<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m81bi_bfe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="m81bi_bfe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:opentelemetry-wordmark" /></template>
