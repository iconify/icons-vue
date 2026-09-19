<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vtdpo8psi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="vtdpo8psi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:ticket" /></template>
