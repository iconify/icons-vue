<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j92as5bdo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j92as5bdo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:square-dashed-close-fill-round" /></template>
