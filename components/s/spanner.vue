<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tf6hpubqv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":16};
const content = `<path class="tf6hpubqv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:spanner" /></template>
