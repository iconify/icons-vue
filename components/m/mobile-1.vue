<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s3x-ekb1m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="s3x-ekb1m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:mobile-1" /></template>
