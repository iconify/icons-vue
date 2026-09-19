<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nna_jvqox.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":16};
const content = `<path class="nna_jvqox"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:tent-camp" /></template>
