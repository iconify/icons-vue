<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/em_k27bbc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="em_k27bbc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:whole-word-sharp-fill" /></template>
