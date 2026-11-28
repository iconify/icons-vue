<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nr3ujtb4j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="nr3ujtb4j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:monitor-slash-thin" /></template>
