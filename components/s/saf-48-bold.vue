<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/djc8x4bhg.css';
import '../../css/i/i24xrk73t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="djc8x4bhg"/><path class="i24xrk73t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:saf-48-bold" /></template>
