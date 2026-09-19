<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z7eta4bwd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="z7eta4bwd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:sunset-1" /></template>
