<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/ddx_2psae.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":39,"height":39};
const content = `<path class="ddx_2psae"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:whoop" /></template>
