<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wcw__-b2h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="wcw__-b2h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:user-activity" /></template>
