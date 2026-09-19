<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cb5qd-b6p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="cb5qd-b6p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:shield" /></template>
