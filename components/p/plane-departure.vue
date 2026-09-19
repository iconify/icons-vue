<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jpuo_eyje.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="jpuo_eyje"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:plane-departure" /></template>
