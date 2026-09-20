<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m45j_9b2g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="m45j_9b2g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:waterfall" /></template>
