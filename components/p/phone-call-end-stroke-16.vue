<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oxhhfyb8o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="oxhhfyb8o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:phone-call-end-stroke-16" /></template>
