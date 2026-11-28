<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nnh8wubts.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nnh8wubts"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:screen-share-x" /></template>
