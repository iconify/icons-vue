<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ekgl8qbch.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ekgl8qbch"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:tally-4-solid" /></template>
