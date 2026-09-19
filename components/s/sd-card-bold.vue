<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ecmp83b2h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="ecmp83b2h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:sd-card-bold" /></template>
