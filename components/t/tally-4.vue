<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fi6gjmbzh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fi6gjmbzh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:tally-4" /></template>
