<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nfhjfo2hk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":16};
const content = `<path class="nfhjfo2hk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:test-tube-empty" /></template>
