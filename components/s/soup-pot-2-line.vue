<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eu4p4krzp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eu4p4krzp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:soup-pot-2-line" /></template>
