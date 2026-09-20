<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jl4enbc6s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jl4enbc6s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:transmute-dark" /></template>
