<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jmmz9qtup.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="jmmz9qtup"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:ticket-duo" /></template>
