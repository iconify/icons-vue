<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/juv1l2bcg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="juv1l2bcg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:text-flow-rows-remix" /></template>
