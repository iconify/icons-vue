<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ups3wbcvu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ups3wbcvu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:surprised-gloss" /></template>
