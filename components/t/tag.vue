<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nax1ayx-j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":16};
const content = `<path class="nax1ayx-j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:tag" /></template>
