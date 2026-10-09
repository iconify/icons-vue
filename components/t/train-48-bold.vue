<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pmcricc-j.css';
import '../../css/i/i90rnaccf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="pmcricc-j"/><path class="i90rnaccf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:train-48-bold" /></template>
