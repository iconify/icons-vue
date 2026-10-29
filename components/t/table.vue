<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mhp4b7gcv.css';
import '../../css/n/nos6nfben.css';
import '../../css/o/o4qtwp2ep.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mhp4b7gcv"/><path class="nos6nfben"/><path class="o4qtwp2ep"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:table" /></template>
