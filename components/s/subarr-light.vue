<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/npm2oqxob.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="npm2oqxob"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:subarr-light" /></template>
