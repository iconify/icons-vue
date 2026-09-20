<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/erj7oo6ms.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="erj7oo6ms"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:perplexity-ai-light" /></template>
