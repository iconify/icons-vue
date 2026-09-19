<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s3ha7mwhy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="s3ha7mwhy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:math" /></template>
