<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gukdrob5p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gukdrob5p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:ringlink-dark" /></template>
