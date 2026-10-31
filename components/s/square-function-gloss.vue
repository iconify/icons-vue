<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nvlk20bxa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nvlk20bxa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:square-function-gloss" /></template>
