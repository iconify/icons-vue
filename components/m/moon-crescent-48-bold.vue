<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pdlgrw2ra.css';
import '../../css/s/skmrpcbag.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="pdlgrw2ra"/><path class="skmrpcbag"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:moon-crescent-48-bold" /></template>
