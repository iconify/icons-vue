<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/trb0p2uxa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":16};
const content = `<path class="trb0p2uxa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:ruler" /></template>
