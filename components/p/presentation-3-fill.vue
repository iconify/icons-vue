<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iwb95wbcs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iwb95wbcs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:presentation-3-fill" /></template>
