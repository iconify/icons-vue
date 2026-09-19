<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bjhb0_cjm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="bjhb0_cjm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:power" /></template>
