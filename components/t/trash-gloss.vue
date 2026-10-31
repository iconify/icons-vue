<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/utd5y4bcs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="utd5y4bcs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:trash-gloss" /></template>
