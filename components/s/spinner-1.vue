<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p8avadbty.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="p8avadbty"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:spinner-1" /></template>
