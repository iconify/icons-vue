<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xbhhc8blo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="xbhhc8blo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:shield-1" /></template>
