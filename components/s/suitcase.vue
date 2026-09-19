<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nqtuv14sk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":16};
const content = `<path class="nqtuv14sk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:suitcase" /></template>
