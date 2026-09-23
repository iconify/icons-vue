<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ew-sr1mcj.css';
import '../../css/m/my_ftigmx.css';
import '../../css/w/w1-6qwzkf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ew-sr1mcj"/><path class="my_ftigmx"/><path class="w1-6qwzkf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:silo-media-server" /></template>
