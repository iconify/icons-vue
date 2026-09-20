<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/idqhxccai.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="idqhxccai"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:microscope-observation-sciene-remix" /></template>
