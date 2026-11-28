<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rjhwy-bts.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="rjhwy-bts"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:replay-10-thin" /></template>
