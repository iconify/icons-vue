<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x4mzg_bvg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="x4mzg_bvg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:media-skip-backward" /></template>
