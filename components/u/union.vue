<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eme_wwb-z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="eme_wwb-z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:union" /></template>
