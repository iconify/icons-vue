<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ix28ohbbv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ix28ohbbv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:screw-driver" /></template>
