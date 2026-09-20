<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rrxs8yb0d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="rrxs8yb0d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:volume-high" /></template>
