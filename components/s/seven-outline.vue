<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/paea7wd2m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="paea7wd2m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:seven-outline" /></template>
