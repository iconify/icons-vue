<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ct8ahm03y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ct8ahm03y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:zoom-question-filled" /></template>
