<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z59x0ffla.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="z59x0ffla"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:message-circle-question-mark-filled" /></template>
