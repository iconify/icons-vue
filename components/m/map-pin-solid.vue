<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/umounmz6u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="umounmz6u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="rivet-icons:map-pin-solid" /></template>
