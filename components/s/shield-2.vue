<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gzhrqib3p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":16};
const content = `<path class="gzhrqib3p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:shield-2" /></template>
