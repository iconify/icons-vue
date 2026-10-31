<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u85-a-bde.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u85-a-bde"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:square-arrow-up-right-round" /></template>
