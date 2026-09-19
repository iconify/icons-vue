<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kghq_fn3a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="kghq_fn3a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:ruler-outline" /></template>
