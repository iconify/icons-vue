<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jyr-wnnqa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jyr-wnnqa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:monitor-lock" /></template>
