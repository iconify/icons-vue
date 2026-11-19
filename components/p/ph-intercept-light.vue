<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rxy12r89z.css';
import '../../css/j/jdijwxbvy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rxy12r89z"/><path class="jdijwxbvy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:ph-intercept-light" /></template>
