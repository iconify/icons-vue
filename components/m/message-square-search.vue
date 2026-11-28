<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rqre4nbte.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rqre4nbte"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:message-square-search" /></template>
