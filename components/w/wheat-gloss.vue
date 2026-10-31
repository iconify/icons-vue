<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r151b58lm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r151b58lm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:wheat-gloss" /></template>
