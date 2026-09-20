<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rkkpxpb1q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="rkkpxpb1q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:pdf-document-filled" /></template>
