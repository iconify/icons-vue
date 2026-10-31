<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ax8ml37id.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ax8ml37id"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:satellite-dish-fill-round" /></template>
