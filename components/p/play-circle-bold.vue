<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wpj_vsb3z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="wpj_vsb3z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:play-circle-bold" /></template>
