<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/puibmpj5f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="puibmpj5f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="subway:play" /></template>
