<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rxtpq1b2e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="rxtpq1b2e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:nintendo" /></template>
