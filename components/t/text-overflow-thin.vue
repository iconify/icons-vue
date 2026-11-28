<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fp-cyjppm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="fp-cyjppm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:text-overflow-thin" /></template>
