<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bblih7otj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="bblih7otj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:w-bold" /></template>
