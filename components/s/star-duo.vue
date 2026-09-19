<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s0mh3lbze.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="s0mh3lbze"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:star-duo" /></template>
