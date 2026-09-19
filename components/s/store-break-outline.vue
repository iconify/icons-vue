<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uv61ubcew.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="uv61ubcew"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:store-break-outline" /></template>
