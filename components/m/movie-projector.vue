<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f69k5ob-g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":17};
const content = `<path class="f69k5ob-g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:movie-projector" /></template>
