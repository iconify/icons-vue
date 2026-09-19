<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h8cnf1h0z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="h8cnf1h0z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:trash-1-bold" /></template>
