<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e2f6qddde.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="e2f6qddde"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:omnipoly-dark" /></template>
