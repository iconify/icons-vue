<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vbd53pbnn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":16};
const content = `<path class="vbd53pbnn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:puzzle" /></template>
