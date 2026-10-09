<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kamd1_bjv.css';
import '../../css/j/jgjn71b8j.css';
import '../../css/c/c65-ehvfy.css';
import '../../css/o/oyertvasq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="kamd1_bjv"/><path class="jgjn71b8j"/><path class="c65-ehvfy"/><path class="oyertvasq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:supermarket-48" /></template>
