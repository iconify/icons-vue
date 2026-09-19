<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mhfvpzb8b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="mhfvpzb8b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:shoe-print" /></template>
