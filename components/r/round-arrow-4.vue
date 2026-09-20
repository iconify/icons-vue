<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gbobdk3yv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gbobdk3yv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="subway:round-arrow-4" /></template>
