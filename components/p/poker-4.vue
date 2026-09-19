<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dwx6ummor.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":16};
const content = `<path class="dwx6ummor"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:poker-4" /></template>
