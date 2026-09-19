<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/olowe0bfz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="olowe0bfz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:spinner-1" /></template>
