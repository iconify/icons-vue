<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c__d53b9x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="c__d53b9x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:tags-fill" /></template>
