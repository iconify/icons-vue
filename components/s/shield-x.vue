<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uj4x2qbig.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uj4x2qbig"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:shield-x" /></template>
