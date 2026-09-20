<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mht9c3b7a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="mht9c3b7a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:serving-dome-remix" /></template>
