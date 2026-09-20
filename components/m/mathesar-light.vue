<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sf73475fd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="sf73475fd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:mathesar-light" /></template>
