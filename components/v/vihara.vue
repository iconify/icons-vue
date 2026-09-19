<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tq8bzlb8n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="tq8bzlb8n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:vihara" /></template>
