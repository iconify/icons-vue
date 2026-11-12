<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f5cbidche.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="f5cbidche"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:mathesar-dark" /></template>
