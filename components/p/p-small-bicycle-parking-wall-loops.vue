<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k_v0wpbwu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="k_v0wpbwu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:p-small-bicycle-parking-wall-loops" /></template>
