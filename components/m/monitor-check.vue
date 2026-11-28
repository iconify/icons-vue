<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r37vede1h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r37vede1h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:monitor-check" /></template>
