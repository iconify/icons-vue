<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ar7ya4bel.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":16};
const content = `<path class="ar7ya4bel"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:quote-open" /></template>
