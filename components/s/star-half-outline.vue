<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b2nrqeb8a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="b2nrqeb8a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:star-half-outline" /></template>
