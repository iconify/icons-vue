<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ras2v3bml.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ras2v3bml"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:voxmedia-coral-dark" /></template>
