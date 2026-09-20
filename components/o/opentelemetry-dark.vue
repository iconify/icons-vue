<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l0sgjwbvp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="l0sgjwbvp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:opentelemetry-dark" /></template>
