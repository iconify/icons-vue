<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y8vsdy3la.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="y8vsdy3la"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:sort-numeric-up" /></template>
