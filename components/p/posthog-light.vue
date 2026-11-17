<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x9g4_sbwz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="x9g4_sbwz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:posthog-light" /></template>
