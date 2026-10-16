<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i6pxhx3fr.css';
import '../../css/b/bj9m5zbrg.css';
import '../../css/e/e13md-fck.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="i6pxhx3fr"/><path class="bj9m5zbrg"/><path class="e13md-fck"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:telemetry-48-bold" /></template>
