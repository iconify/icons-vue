<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rafffx2tr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rafffx2tr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:photo-camera" /></template>
