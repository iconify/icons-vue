<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gkan5c65j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="gkan5c65j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:tablet" /></template>
