<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f-iu0r2yz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="f-iu0r2yz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:picnic-table-bold" /></template>
