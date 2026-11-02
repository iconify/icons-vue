<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vlwbs1dqf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vlwbs1dqf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:user-warning-line" /></template>
