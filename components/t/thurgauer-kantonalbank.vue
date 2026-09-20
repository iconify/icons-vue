<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q0q031bbs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q0q031bbs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:thurgauer-kantonalbank" /></template>
