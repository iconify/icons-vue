<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g4pv2vbrn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="g4pv2vbrn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:posthog-dark" /></template>
