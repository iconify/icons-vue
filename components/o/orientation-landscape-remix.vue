<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cpzkk_byh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="cpzkk_byh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:orientation-landscape-remix" /></template>
