<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h8l_brb1r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h8l_brb1r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:number-4-duocolor-round" /></template>
