<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ku6mcablf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":16};
const content = `<path class="ku6mcablf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:upstair" /></template>
