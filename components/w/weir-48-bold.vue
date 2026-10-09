<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/puoj9enyr.css';
import '../../css/m/mkvae1bnc.css';
import '../../css/z/z6fy8jbcw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="puoj9enyr"/><path class="mkvae1bnc"/><path class="z6fy8jbcw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:weir-48-bold" /></template>
