<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mny6kj1pr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="mny6kj1pr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:tactile-paving-x-5" /></template>
