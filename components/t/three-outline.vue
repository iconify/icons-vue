<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sj170dafj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="sj170dafj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:three-outline" /></template>
