<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tt8gsz3uj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="tt8gsz3uj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:pen-bold" /></template>
