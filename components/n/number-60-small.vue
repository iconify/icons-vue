<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w47rdybzi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w47rdybzi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:number-60-small" /></template>
