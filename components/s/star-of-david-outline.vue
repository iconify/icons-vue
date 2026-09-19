<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lq9y3hb5i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="lq9y3hb5i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:star-of-david-outline" /></template>
