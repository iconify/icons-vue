<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dcta_v5_z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="dcta_v5_z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:q-outline" /></template>
