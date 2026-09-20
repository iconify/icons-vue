<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/paqxdte2e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="paqxdte2e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:question-in-circle" /></template>
