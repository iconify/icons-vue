<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/obxa5ggcr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="obxa5ggcr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:square-arrow-right-sharp-fill" /></template>
