<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vp5jewbjm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="vp5jewbjm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:male" /></template>
