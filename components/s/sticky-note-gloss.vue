<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c4_3vwozi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c4_3vwozi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:sticky-note-gloss" /></template>
