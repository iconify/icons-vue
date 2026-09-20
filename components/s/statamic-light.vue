<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yn0z7abwo.css';
import '../../css/v/vi98df-3j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="yn0z7abwo"/><path class="vi98df-3j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:statamic-light" /></template>
