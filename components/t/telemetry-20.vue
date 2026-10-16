<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ll0lbeozm.css';
import '../../css/j/jaxt8ed6x.css';
import '../../css/c/czwa2emeh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ll0lbeozm"/><path class="jaxt8ed6x"/><path class="czwa2emeh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:telemetry-20" /></template>
