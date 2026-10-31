<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/accjx1bsi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="accjx1bsi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:square-info-round" /></template>
