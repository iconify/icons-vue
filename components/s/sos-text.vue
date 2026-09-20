<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/unsv5v4cm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="unsv5v4cm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:sos-text" /></template>
