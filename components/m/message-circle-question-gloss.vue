<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aatmnibqj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aatmnibqj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:message-circle-question-gloss" /></template>
