<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rtsxvz0cl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="rtsxvz0cl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:palm-bottom-right-horizontal-line" /></template>
