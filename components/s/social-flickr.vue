<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dg3dtm9tv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="dg3dtm9tv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="foundation:social-flickr" /></template>
