<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pb5vv-0rq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="pb5vv-0rq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:printer-outline" /></template>
