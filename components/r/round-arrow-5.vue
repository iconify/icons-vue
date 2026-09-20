<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/flpk8vi4p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="flpk8vi4p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="subway:round-arrow-5" /></template>
