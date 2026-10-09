<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rsjqddezd.css';
import '../../css/d/ds9x_zbhf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="rsjqddezd"/><path class="ds9x_zbhf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:smart-grid-48" /></template>
