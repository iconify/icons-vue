<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yfyu3jekb.css';
import '../../css/f/fc-7_47pi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="yfyu3jekb"/><path class="fc-7_47pi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:mushroom-48" /></template>
