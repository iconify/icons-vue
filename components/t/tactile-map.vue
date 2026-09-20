<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ra19rmbjq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ra19rmbjq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:tactile-map" /></template>
