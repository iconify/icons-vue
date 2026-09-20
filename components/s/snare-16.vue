<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wyvsgsbdp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="wyvsgsbdp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:snare-16" /></template>
