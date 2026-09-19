<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hj1u2fbvd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":424,"height":496};
const content = `<path class="hj1u2fbvd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:sort-by-alpha" /></template>
