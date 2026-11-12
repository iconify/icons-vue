<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nxa_hyp1o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="nxa_hyp1o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:t3-code-light" /></template>
