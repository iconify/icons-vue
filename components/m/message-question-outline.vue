<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fu7_340-i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fu7_340-i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:message-question-outline" /></template>
