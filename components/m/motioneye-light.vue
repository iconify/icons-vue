<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ivimh0l5c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ivimh0l5c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:motioneye-light" /></template>
