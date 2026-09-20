<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v5q7p6dir.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="v5q7p6dir"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:phylum-dark" /></template>
