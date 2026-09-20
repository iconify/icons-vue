<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y1b9w0esc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y1b9w0esc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:note-circle-outline" /></template>
