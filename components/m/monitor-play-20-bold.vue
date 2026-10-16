<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k_736ebfb.css';
import '../../css/w/w0poz4bns.css';
import '../../css/h/h3-00cbib.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="k_736ebfb"/><path class="w0poz4bns"/><path class="h3-00cbib"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:monitor-play-20-bold" /></template>
