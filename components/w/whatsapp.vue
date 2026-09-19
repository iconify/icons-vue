<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qin0occ5a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1536,"height":1600};
const content = `<path class="qin0occ5a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:whatsapp" /></template>
