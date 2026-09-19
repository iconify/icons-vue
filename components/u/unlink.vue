<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bt8pu_u7k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="bt8pu_u7k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:unlink" /></template>
