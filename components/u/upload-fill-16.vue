<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wv25jylpb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="wv25jylpb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:upload-fill-16" /></template>
