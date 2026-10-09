<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s3qc5obqr.css';
import '../../css/m/mwc9o5b_m.css';
import '../../css/i/ine-7ac_y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="s3qc5obqr"/><path class="mwc9o5b_m"/><path class="ine-7ac_y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:ore-48-bold" /></template>
