<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oyuccgiib.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oyuccgiib"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:workflow-round" /></template>
