<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x81gyeeka.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="x81gyeeka"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:squircle" /></template>
