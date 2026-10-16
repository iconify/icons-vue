<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/da8ahcs8d.css';
import '../../css/f/fhiwyn5qd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="da8ahcs8d"/><path class="fhiwyn5qd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:subscript-48" /></template>
