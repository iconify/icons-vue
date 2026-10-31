<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j36ac2b3k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j36ac2b3k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:message-square-warning-gloss" /></template>
