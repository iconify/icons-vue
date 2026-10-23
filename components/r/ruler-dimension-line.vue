<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pbb0ayics.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pbb0ayics"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:ruler-dimension-line" /></template>
