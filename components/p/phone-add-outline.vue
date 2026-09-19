<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c7ap2g0om.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="c7ap2g0om"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:phone-add-outline" /></template>
