<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/njmj_ab4y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":16};
const content = `<path class="njmj_ab4y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:picture-2" /></template>
