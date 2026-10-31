<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q4s20ps9s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q4s20ps9s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:plus-duocolor-round" /></template>
