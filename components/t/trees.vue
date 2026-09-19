<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a03eb3b2b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":16};
const content = `<path class="a03eb3b2b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:trees" /></template>
