<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s0e89qu-d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="s0e89qu-d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:table-density-normal" /></template>
