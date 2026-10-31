<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t4se-c4fp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t4se-c4fp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:square-dashed-square-top-left-round" /></template>
