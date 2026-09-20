<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r3qt8sbaz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="r3qt8sbaz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:owntracks-light" /></template>
