<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oo8r5ubdl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="oo8r5ubdl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oi:media-skip-backward" /></template>
