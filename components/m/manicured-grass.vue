<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nbn5igc_g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="nbn5igc_g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:manicured-grass" /></template>
