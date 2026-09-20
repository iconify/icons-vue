<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pkhl2obdc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="pkhl2obdc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:play-small-16" /></template>
