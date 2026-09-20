<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ur913e2io.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ur913e2io"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:mixpost-dark" /></template>
