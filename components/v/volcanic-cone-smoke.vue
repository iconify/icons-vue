<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/awckl0dec.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="awckl0dec"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:volcanic-cone-smoke" /></template>
