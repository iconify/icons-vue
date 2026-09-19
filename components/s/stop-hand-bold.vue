<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xx7u_3bsv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="xx7u_3bsv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:stop-hand-bold" /></template>
