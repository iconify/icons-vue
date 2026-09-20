<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wy4cmqgds.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wy4cmqgds"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:tally-2" /></template>
