<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aq-c0rbrg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1664,"height":1600};
const content = `<path class="aq-c0rbrg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vs:sticky-note" /></template>
