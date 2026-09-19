<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n557phlxo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":17};
const content = `<path class="n557phlxo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:sound" /></template>
