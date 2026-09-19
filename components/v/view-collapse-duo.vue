<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tr_lmabvd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="tr_lmabvd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:view-collapse-duo" /></template>
