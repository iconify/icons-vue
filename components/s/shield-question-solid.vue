<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ebxydcblb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ebxydcblb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:shield-question-solid" /></template>
