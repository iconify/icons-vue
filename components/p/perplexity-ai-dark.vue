<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w_qh4u67n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="w_qh4u67n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:perplexity-ai-dark" /></template>
