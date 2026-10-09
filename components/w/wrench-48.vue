<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jbiwgmbyr.css';
import '../../css/h/hbyu2bdtl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="jbiwgmbyr"/><path class="hbyu2bdtl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:wrench-48" /></template>
