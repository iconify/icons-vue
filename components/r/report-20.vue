<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/re0n-jb1b.css';
import '../../css/o/ooz3o6s1d.css';
import '../../css/o/o76rkrbtm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="re0n-jb1b"/><path class="ooz3o6s1d"/><path class="o76rkrbtm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:report-20" /></template>
