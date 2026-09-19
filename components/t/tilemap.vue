<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s4-2nzkwb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="s4-2nzkwb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:tilemap" /></template>
