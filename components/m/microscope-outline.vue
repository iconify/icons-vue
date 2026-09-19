<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g0rnk_b6a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="g0rnk_b6a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:microscope-outline" /></template>
