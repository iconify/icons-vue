<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/it9cnwzdt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="it9cnwzdt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:satellite" /></template>
