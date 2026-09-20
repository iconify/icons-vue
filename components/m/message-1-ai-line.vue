<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/re49dk2cy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="re49dk2cy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:message-1-ai-line" /></template>
