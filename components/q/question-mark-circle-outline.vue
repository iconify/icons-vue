<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g6puw5bim.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g6puw5bim"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:question-mark-circle-outline" /></template>
