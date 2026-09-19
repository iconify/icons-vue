<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rxn3dhv8k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="rxn3dhv8k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:telephone-box" /></template>
