<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gskjgiboa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="gskjgiboa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:text-bold" /></template>
