<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pn9b94bna.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="pn9b94bna"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="foundation:play" /></template>
