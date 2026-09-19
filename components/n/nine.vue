<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c-9iiqe2g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="c-9iiqe2g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:nine" /></template>
