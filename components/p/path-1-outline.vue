<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m32h73d6t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="m32h73d6t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:path-1-outline" /></template>
