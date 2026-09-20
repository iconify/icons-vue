<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f7z33-zvs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="f7z33-zvs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:pickup-truck-with-slidein-camper" /></template>
