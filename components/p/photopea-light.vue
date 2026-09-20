<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d5y1f8b5l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="d5y1f8b5l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:photopea-light" /></template>
