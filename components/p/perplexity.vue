<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cy8405bfr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="cy8405bfr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:perplexity" /></template>
