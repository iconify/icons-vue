<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n41p3s9mq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="n41p3s9mq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:vertexshader" /></template>
