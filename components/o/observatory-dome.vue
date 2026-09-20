<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j9c6o_bmx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="j9c6o_bmx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:observatory-dome" /></template>
