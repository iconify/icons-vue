<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/naq_9b0-d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="naq_9b0-d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:paw-plus" /></template>
