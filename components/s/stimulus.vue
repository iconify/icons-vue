<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n99vqw96w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="n99vqw96w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:stimulus" /></template>
