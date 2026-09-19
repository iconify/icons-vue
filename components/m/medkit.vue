<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i_3v7z53s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1792,"height":1536};
const content = `<path class="i_3v7z53s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:medkit" /></template>
