<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/da46_l89g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="da46_l89g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:payloadcms-wordmark" /></template>
