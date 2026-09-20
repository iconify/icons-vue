<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zdlqjf2ga.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zdlqjf2ga"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:rss-symbol-solid" /></template>
