<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/covvo99ya.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":16};
const content = `<path class="covvo99ya"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:pen" /></template>
