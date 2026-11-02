<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ee7w3zqxg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ee7w3zqxg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:scrollable-list-fill" /></template>
