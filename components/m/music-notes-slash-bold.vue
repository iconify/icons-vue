<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jwh_2034p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="jwh_2034p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:music-notes-slash-bold" /></template>
