<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h80tcrb5h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="h80tcrb5h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:y-bold" /></template>
