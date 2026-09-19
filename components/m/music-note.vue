<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/em3hccbqp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="em3hccbqp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:music-note" /></template>
