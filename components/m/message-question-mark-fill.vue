<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/quif2tamo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="quif2tamo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:message-question-mark-fill" /></template>
