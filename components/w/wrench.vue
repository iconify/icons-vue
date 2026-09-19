<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jefc31vvu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":16};
const content = `<path class="jefc31vvu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:wrench" /></template>
