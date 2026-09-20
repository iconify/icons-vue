<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bu_9opbfl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bu_9opbfl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:square-chevron-up-fill" /></template>
