<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x80n7zxwc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="x80n7zxwc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:monitor" /></template>
