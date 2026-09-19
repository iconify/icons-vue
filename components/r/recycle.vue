<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vexk7p94v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vexk7p94v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:recycle" /></template>
