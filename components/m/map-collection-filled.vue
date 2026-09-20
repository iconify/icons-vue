<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j25hdxidg.css';
import '../../css/e/esl7uqcwy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j25hdxidg"/><path class="esl7uqcwy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:map-collection-filled" /></template>
