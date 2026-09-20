<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m63vg2bps.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":11,"height":11};
const content = `<path class="m63vg2bps"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:marker-stroked-11" /></template>
