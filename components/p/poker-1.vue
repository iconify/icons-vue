<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ujm4itb3b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":17};
const content = `<path class="ujm4itb3b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:poker-1" /></template>
