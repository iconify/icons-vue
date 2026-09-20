<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sxafg2elz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="sxafg2elz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:obelisk" /></template>
