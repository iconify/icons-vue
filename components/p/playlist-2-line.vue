<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gq_wvc0jz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gq_wvc0jz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:playlist-2-line" /></template>
