<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/exba11bdo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="exba11bdo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:star-badge-remix" /></template>
