<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rnb5g8bpa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="rnb5g8bpa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:wall-front-gate" /></template>
