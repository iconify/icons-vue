<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n6tf23b2i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="n6tf23b2i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="osmic:taxi-14" /></template>
