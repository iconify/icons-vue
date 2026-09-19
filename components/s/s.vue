<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b5jo79bck.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="b5jo79bck"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:s" /></template>
