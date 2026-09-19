<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lvunwrboe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="lvunwrboe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:mobile" /></template>
