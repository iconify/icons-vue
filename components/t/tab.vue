<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v-bib9iuo.css';
import '../../css/u/u2_or7bit.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v-bib9iuo"/><path clip-rule="evenodd" class="u2_or7bit"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:tab" /></template>
