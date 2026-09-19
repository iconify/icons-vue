<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w9c3jne9d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="w9c3jne9d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:six-outline" /></template>
