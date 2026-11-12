<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qtmawi7ic.css';
import '../../css/e/e558ozb4n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qtmawi7ic"/><path class="e558ozb4n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:nasa-light" /></template>
