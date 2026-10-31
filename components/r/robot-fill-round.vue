<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ofhs6k5it.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ofhs6k5it"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:robot-fill-round" /></template>
