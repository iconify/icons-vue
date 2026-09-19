<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tse4dim5c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="tse4dim5c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:pen-fountain-bold" /></template>
