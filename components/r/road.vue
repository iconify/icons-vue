<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vp3lfk64n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":16};
const content = `<path class="vp3lfk64n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:road" /></template>
