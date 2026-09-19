<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dbqv5ub4i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":16};
const content = `<path class="dbqv5ub4i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:site-map" /></template>
