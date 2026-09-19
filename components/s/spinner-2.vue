<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hs84ht5uq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="hs84ht5uq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:spinner-2" /></template>
