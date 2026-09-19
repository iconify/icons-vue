<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z7pga0bny.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="z7pga0bny"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:md-redo" /></template>
