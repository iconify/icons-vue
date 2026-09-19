<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rro55svmo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="rro55svmo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:n-bold" /></template>
