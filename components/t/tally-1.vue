<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/barz0mwnr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="barz0mwnr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:tally-1" /></template>
