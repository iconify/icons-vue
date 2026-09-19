<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tg86byjmf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="tg86byjmf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:sort-size-up-1" /></template>
