<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kw9uoouzq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":16};
const content = `<path class="kw9uoouzq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:screw" /></template>
