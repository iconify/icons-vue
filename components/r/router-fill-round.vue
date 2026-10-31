<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cq13o4b6d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cq13o4b6d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:router-fill-round" /></template>
