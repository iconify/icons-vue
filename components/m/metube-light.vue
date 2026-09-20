<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e-a0zoblt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="e-a0zoblt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:metube-light" /></template>
