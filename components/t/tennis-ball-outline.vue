<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mzpg0f4dd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="mzpg0f4dd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:tennis-ball-outline" /></template>
