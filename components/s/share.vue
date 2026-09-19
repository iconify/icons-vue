<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tlsu96b9v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="tlsu96b9v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:share" /></template>
