<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l6x5z1bdn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="l6x5z1bdn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:tablet-outline" /></template>
