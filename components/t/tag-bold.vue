<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a71-6xbfq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="a71-6xbfq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:tag-bold" /></template>
