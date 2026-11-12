<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cg8csnzhc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="cg8csnzhc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:weaviate-light" /></template>
