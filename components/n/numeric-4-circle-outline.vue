<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bzi_0qbmf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bzi_0qbmf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:numeric-4-circle-outline" /></template>
