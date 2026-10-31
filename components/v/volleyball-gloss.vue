<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/twj1lm13k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="twj1lm13k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:volleyball-gloss" /></template>
