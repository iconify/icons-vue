<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jse3np_ai.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jse3np_ai"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:stroke-line-cap-square-filled" /></template>
