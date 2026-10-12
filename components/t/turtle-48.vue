<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/goe_lpbge.css';
import '../../css/f/fq6fmdr9f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="goe_lpbge"/><path class="fq6fmdr9f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:turtle-48" /></template>
