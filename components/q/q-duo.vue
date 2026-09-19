<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/or8-05bqx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="or8-05bqx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:q-duo" /></template>
