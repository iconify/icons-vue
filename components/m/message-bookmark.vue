<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oma-vc_qi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oma-vc_qi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:message-bookmark" /></template>
