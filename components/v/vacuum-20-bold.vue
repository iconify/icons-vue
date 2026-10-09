<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r8gpsn7-o.css';
import '../../css/n/nbr-frb3w.css';
import '../../css/c/cs47l5nhg.css';
import '../../css/d/dpbszfs_x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="r8gpsn7-o"/><path class="nbr-frb3w"/><path class="cs47l5nhg"/><path class="dpbszfs_x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:vacuum-20-bold" /></template>
