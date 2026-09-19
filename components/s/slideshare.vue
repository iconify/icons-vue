<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fxle2tv-p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":464,"height":448};
const content = `<path class="fxle2tv-p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:slideshare" /></template>
