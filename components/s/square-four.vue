<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g66re9w6x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":16};
const content = `<path class="g66re9w6x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:square-four" /></template>
