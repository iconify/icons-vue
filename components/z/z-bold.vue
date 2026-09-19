<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t9zmu4brs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="t9zmu4brs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:z-bold" /></template>
