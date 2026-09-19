<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uaa-vxyjp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="uaa-vxyjp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:union-outline" /></template>
