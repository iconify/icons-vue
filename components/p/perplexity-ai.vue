<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/re5699mtq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="re5699mtq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:perplexity-ai" /></template>
