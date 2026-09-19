<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d7zlwfbdy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<rect class="d7zlwfbdy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:rectangle-bold" /></template>
