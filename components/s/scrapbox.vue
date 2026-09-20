<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/je-ibh20q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="je-ibh20q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:scrapbox" /></template>
