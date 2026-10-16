<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pi4epefpx.css';
import '../../css/o/oiwmoi7co.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="pi4epefpx"/><path class="oiwmoi7co"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:smart-speaker-20-bold" /></template>
