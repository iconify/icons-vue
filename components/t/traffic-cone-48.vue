<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rl79hl11f.css';
import '../../css/m/m2n9dacld.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="rl79hl11f"/><path class="m2n9dacld"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:traffic-cone-48" /></template>
