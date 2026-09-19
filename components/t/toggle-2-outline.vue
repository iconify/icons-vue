<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r75m5p1ee.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="r75m5p1ee"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:toggle-2-outline" /></template>
