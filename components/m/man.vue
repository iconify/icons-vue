<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tpx8-5bte.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="tpx8-5bte"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:man" /></template>
