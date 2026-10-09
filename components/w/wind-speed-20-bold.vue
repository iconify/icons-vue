<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nuzmv1qpb.css';
import '../../css/p/p_zjrxi1a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="nuzmv1qpb"/><path class="p_zjrxi1a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:wind-speed-20-bold" /></template>
