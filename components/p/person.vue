<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a9l_web1w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="a9l_web1w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:person" /></template>
