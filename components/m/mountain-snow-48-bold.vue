<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pg1-fhq_s.css';
import '../../css/p/p9d7ykejn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="pg1-fhq_s"/><path class="p9d7ykejn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:mountain-snow-48-bold" /></template>
