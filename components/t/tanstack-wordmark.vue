<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iq-mk8b4h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="iq-mk8b4h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:tanstack-wordmark" /></template>
