<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jsjmd0byc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jsjmd0byc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:plumio-dark" /></template>
