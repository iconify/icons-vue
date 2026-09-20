<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mo5dze5xl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mo5dze5xl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:music-note-variant" /></template>
